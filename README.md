# LogPulseSynapse

LogPulseSynapse monitors the pulse of log activity from multiple systems and correlates dips, surges, or silent failures across time windows and sources.

## Features
- Pulse pattern analysis per source or service.
- Drop/spike detection via moving window average.
- Live anomaly alerting and silent period detection.
- Easily integrates with journald, syslog, or logstash.

## Usage
```bash
git clone https://github.com/your-org/LogPulseSynapse.git
cd LogPulseSynapse
python logpulse/ingest.py logs/web.log

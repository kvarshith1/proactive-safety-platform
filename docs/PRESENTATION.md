# Proactive Safety — Presentation

## Slide 1 — Title

**Intelligent Proactive Road, Travel and Emergency Safety Platform**

**Proactive Safety**

> Detect danger. Warn early.

A technology platform designed to provide road users with an early warning before a potential road conflict becomes an accident.

---

## Slide 2 — The Problem

Road users can misjudge:

- Vehicle speed
- Vehicle distance
- Visibility at night
- Junction risk
- Movement of approaching vehicles

At an unsafe junction or crossing, a few seconds of warning can matter.

**Problem:** Traditional emergency systems mainly respond after an incident. The opportunity is to provide useful information before the conflict occurs.

---

## Slide 3 — The Real-World Scenario

### Example scenario

- Around 9 PM
- Highway junction
- Poor visibility and inadequate lighting
- Two-wheeler with two occupants
- An approaching car is travelling at high speed
- The riders see the vehicle but misjudge its speed/distance
- A collision occurs

### Key question

**What if the road user had received a warning before entering the dangerous conflict area?**

---

## Slide 4 — Our Idea

### Proactive Safety

Instead of:

```text
ACCIDENT
   ↓
DETECTION
   ↓
RESPONSE
```

the system aims for:

```text
HAZARD DETECTION
       ↓
EARLY WARNING
       ↓
USER REACTION
       ↓
POSSIBLE CONFLICT AVOIDANCE
```

The focus is **prevention through early awareness**.

---

## Slide 5 — How the System Works

The system combines:

- GPS location
- Current speed
- Heading/direction
- Known high-risk zones
- Nearby participating app users
- Road and visibility information
- Accident history associated with risk zones

These inputs are processed by the risk and cooperative safety engines to generate a safety assessment.

---

## Slide 6 — Risk Engine

The system calculates a risk score from **0 to 100**.

| Level | Score | Meaning |
|---|---:|---|
| LOW | 0–30 | Low detected risk |
| MEDIUM | 31–60 | Increased awareness required |
| HIGH | 61–80 | Slow down / prepare to stop |
| CRITICAL | 81–100 | Immediate safety action |

The assessment also provides contributing factors and a recommended action instead of displaying only a number.

---

## Slide 7 — Cooperative Safety

A major capability is communication between participating road users.

```text
Vehicle / Phone A
GPS + Speed + Heading
        │
        ▼
     Backend
        ▲
        │
GPS + Speed + Heading
Vehicle / Phone B
```

The backend can compare participating vehicles and identify:

- Opposite-direction path conflicts
- Potential closest-approach conflicts
- Junction conflicts
- Time-to-conflict
- Closing speed

The system can then return a warning to the affected app users.

---

## Slide 8 — Android Application

The Android application provides the device-side safety experience.

### Main capabilities

- Live GPS monitoring
- Speed estimation
- Heading information
- Real map view
- Risk-zone awareness
- Nearby app-user awareness
- Conflict warnings
- Notification and vibration support
- Text-to-speech warning support
- SOS action

The app is designed around real device location rather than only a simulated map.

---

## Slide 9 — Web Platform & Backend

### Web interface

Provides:

- Journey monitoring
- Risk score
- Closing speed
- Time-to-conflict
- Risk factors
- Recommended action
- SOS controls
- Risk-zone management
- Demonstration controls

### Backend

Provides APIs for:

- Health monitoring
- Risk-zone data
- Cooperative location updates
- Active vehicle information
- Conflict alerts

---

## Slide 10 — Current Limitation

A phone cannot reliably know the speed of a completely unrelated vehicle using only its own GPS.

Therefore, the current cooperative model focuses on **vehicles whose users are running the Proactive Safety application**.

For non-app vehicles, future versions can integrate:

- Computer vision
- Camera-based detection
- Connected vehicles
- Roadside radar/sensors
- Traffic authority data

This distinction keeps the current technical implementation realistic.

---

## Slide 11 — Future Scope

Future development can extend the platform with:

- AI/computer-vision vehicle detection
- Better trajectory prediction
- Larger real-world risk datasets
- Road-condition and traffic data
- Connected-vehicle communication
- Roadside sensors
- Improved false-alert reduction
- Emergency-service integration
- Production-grade privacy and authentication

---

## Slide 12 — Final Message

### Road safety should begin before the collision.

**Proactive Safety** aims to turn road information into an early warning so that a driver or rider has more time to make a safer decision.

> **Detect danger. Warn early. Help prevent the conflict.**

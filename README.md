
<br/>
<div align="center" >
    <h1 > ***⚡Hi, I'm Thiago***</h1>

<div align="center">
    <img width="70" height="70" src="https://img.icons8.com/color/48/java-coffee-cup-logo--v1.png" alt="java-coffee-cup-logo--v1"/>
    <img width="70" height="70" src="https://img.icons8.com/color/48/spring-logo.png" alt="spring-logo"/>
    <img width="70" height="70" src="https://img.icons8.com/fluency/48/flutter.png" alt="flutter"/>
    
</div>
<br/>
<div class="person-container" style = " .person-container {
        position: relative;
        width: 100px;
        height: 200px;
        animation: jump 1s infinite alternate;
    }

    .person {
        position: absolute;
        bottom: 0;
        left: 50%;
        transform: translateX(-50%);
        width: 50px;
        height: 100px;
        background-color: #3498db;
        border-radius: 50%;
        animation: jump-legs 1s infinite alternate;
    }

    .person::before,
    .person::after {
        content: '';
        position: absolute;
        width: 20px;
        height: 30px;
        background-color: #2ecc71;
        border-radius: 50%;
        bottom: 100%;
    }

    .person::before {
        left: 15%;
        transform-origin: bottom right;
        animation: jump-arm1 1s infinite alternate;
    }

    .person::after {
        right: 15%;
        transform-origin: bottom left;
        animation: jump-arm2 1s infinite alternate;
    }

    @keyframes jump {
        0%, 100% {
            transform: translateY(0);
        }
        50% {
            transform: translateY(-50px);
        }
    }

    @keyframes jump-legs {
        0%, 100% {
            transform: scaleY(1);
        }
        50% {
            transform: scaleY(0.8);
        }
    }

    @keyframes jump-arm1 {
        0%, 100% {
            transform: rotate(0);
        }
        50% {
            transform: rotate(-45deg);
        }
    }

    @keyframes jump-arm2 {
        0%, 100% {
            transform: rotate(0);
        }
        50% {
            transform: rotate(45deg);
        }
    }">
    <div class="person"></div>
</div>

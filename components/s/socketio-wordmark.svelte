<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/y3wwogb_e.css';
import '../../css/o/omos15brj.css';
import '../../css/n/np6wssw9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="bi12bsetm"><path class="y3wwogb_e"/><path class="omos15brj"/><path class="np6wssw9i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:socketio-wordmark" {...props}></Icon>

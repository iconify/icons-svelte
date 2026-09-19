<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-tflgzje.css';
import '../../css/i/ik34--bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q-tflgzje"/><path class="ik34--bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:time-outline" {...props}></Icon>

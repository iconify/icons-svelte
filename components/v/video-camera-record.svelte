<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrhjw7bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jrhjw7bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:video-camera-record" {...props}></Icon>

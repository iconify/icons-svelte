<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzmq702cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzmq702cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:thumbsup-24" {...props}></Icon>

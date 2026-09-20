<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9onc0b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9onc0b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:soundwave-expressive" {...props}></Icon>

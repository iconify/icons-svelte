<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wducweb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wducweb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:router-check" {...props}></Icon>

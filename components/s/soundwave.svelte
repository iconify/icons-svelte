<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydgy161ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydgy161ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:soundwave" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe3c2ebyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qe3c2ebyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:tidal" {...props}></Icon>

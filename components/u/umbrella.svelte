<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrfdgjb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xrfdgjb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:umbrella" {...props}></Icon>

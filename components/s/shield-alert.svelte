<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryhcp-7eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ryhcp-7eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shield-alert" {...props}></Icon>

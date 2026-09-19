<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg_6_5bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sg_6_5bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:view-dashboard" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl_42w8qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dl_42w8qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:script" {...props}></Icon>

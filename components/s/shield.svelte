<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtdbs_u4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vtdbs_u4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:shield" {...props}></Icon>

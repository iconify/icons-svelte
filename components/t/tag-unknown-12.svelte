<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybvce78ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ybvce78ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:tag-unknown-12" {...props}></Icon>

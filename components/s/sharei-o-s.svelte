<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk0fm-s0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yk0fm-s0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:sharei-o-s" {...props}></Icon>

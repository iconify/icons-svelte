<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz3tp_bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jz3tp_bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:tag-unknown-12-mirror" {...props}></Icon>

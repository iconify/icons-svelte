<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baag32u7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="baag32u7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shield-2-duo" {...props}></Icon>

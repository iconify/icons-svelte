<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix-etju_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ix-etju_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:seek-skip-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-v_5bcnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="c-v_5bcnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shield-duo" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq0240abk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dq0240abk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:x-cross" {...props}></Icon>

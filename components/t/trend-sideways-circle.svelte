<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5jv108xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="j5jv108xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:trend-sideways-circle" {...props}></Icon>

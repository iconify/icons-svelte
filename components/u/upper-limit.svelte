<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o884eac-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o884eac-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:upper-limit" {...props}></Icon>

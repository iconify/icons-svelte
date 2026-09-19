<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmpz-2bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":456};
const content = `<path class="cmpz-2bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:timer" {...props}></Icon>

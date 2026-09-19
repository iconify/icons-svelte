<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj45sdbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lj45sdbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tag" {...props}></Icon>

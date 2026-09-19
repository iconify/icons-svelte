<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv5lx9b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xv5lx9b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:volume-1" {...props}></Icon>

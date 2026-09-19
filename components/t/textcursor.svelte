<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asc_5xb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":1024};
const content = `<path class="asc_5xb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:textcursor" {...props}></Icon>

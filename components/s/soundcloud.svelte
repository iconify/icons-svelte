<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h60wulb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="h60wulb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:soundcloud" {...props}></Icon>

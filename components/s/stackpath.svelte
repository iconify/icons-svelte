<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slafz4i6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="slafz4i6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:stackpath" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfjc3hbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sfjc3hbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:work-case" {...props}></Icon>

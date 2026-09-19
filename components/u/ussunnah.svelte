<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfx4nus2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cfx4nus2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:ussunnah" {...props}></Icon>

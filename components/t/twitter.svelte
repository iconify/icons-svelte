<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjjyxrnjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xjjyxrnjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:twitter" {...props}></Icon>

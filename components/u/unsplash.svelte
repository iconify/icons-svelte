<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mql1jc4bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="mql1jc4bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:unsplash" {...props}></Icon>

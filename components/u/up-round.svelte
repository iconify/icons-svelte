<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xct43n9vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xct43n9vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:up-round" {...props}></Icon>

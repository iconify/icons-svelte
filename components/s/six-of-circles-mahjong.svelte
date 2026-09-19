<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp61wiopl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="cp61wiopl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:six-of-circles-mahjong" {...props}></Icon>

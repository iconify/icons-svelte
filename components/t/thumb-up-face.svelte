<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhqqs--zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vhqqs--zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:thumb-up-face" {...props}></Icon>

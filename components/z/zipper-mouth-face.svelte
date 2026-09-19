<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpao0wblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mpao0wblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:zipper-mouth-face" {...props}></Icon>

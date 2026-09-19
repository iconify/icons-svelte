<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv2_p-9yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="mv2_p-9yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:stumbleupon-circle" {...props}></Icon>

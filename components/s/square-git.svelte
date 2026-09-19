<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vou3_l7ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="vou3_l7ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-git" {...props}></Icon>

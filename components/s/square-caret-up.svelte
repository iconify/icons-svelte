<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eia9bxwwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="eia9bxwwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:square-caret-up" {...props}></Icon>

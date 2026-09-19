<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt-hjub7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="xt-hjub7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:v" {...props}></Icon>

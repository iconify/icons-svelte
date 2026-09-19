<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g33lylbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="g33lylbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:yen-sign" {...props}></Icon>

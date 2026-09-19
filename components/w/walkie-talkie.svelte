<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx85bbbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="xx85bbbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:walkie-talkie" {...props}></Icon>

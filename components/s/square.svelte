<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0yugsbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="z0yugsbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:square" {...props}></Icon>

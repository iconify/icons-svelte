<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5no9zxmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5no9zxmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:truck" {...props}></Icon>

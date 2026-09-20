<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjz52tsns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tjz52tsns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:template-add-rtl" {...props}></Icon>

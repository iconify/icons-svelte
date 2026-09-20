<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moqj_8bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="moqj_8bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:template-add-ltr" {...props}></Icon>

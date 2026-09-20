<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0-ge9aao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v0-ge9aao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:sandbox" {...props}></Icon>

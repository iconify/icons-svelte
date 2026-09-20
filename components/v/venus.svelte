<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs2yn_btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vs2yn_btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:venus" {...props}></Icon>

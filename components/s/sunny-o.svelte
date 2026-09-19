<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrgg98-gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrgg98-gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:sunny-o" {...props}></Icon>

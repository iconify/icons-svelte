<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd38xbbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd38xbbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:search" {...props}></Icon>

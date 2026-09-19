<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pch346b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pch346b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:star-outline" {...props}></Icon>

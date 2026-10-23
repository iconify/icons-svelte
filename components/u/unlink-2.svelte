<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp47o4bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp47o4bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:unlink-2" {...props}></Icon>

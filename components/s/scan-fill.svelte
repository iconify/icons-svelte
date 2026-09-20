<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txzu4-dhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txzu4-dhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:scan-fill" {...props}></Icon>

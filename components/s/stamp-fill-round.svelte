<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf1evobxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf1evobxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:stamp-fill-round" {...props}></Icon>

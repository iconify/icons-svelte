<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9f5_bofv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9f5_bofv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shrub" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfmwocbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfmwocbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:trending-up" {...props}></Icon>

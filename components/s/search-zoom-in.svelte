<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxie47bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxie47bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-zoom-in" {...props}></Icon>

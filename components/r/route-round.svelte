<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/locjvi_oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="locjvi_oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:route-round" {...props}></Icon>

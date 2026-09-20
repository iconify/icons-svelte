<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2dheq6ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2dheq6ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ubisoft" {...props}></Icon>

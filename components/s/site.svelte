<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx71kxbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx71kxbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:site" {...props}></Icon>

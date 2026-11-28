<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eryr_sldj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eryr_sldj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:user-arrow-right" {...props}></Icon>

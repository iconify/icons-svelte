<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwxf3bbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwxf3bbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shuffle-line" {...props}></Icon>

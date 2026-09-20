<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm03u66vf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zm03u66vf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:spiral-shape-remix" {...props}></Icon>

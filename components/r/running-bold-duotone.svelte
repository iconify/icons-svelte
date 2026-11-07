<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqpl8jb6z.css';
import '../../css/v/vamw6spgm.css';
import '../../css/j/j2l4c4iul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqpl8jb6z"/><path clip-rule="evenodd" class="vamw6spgm"/><path class="j2l4c4iul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:running-bold-duotone" {...props}></Icon>

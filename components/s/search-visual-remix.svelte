<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdt20x-2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bdt20x-2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:search-visual-remix" {...props}></Icon>

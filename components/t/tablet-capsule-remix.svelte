<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkmcn9brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bkmcn9brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tablet-capsule-remix" {...props}></Icon>

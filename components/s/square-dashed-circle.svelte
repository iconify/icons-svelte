<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn9yt1bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rn9yt1bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:square-dashed-circle" {...props}></Icon>

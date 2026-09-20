<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4hrepb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u4hrepb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:stagecoach" {...props}></Icon>

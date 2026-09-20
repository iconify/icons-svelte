<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i24d3zwii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i24d3zwii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-dogs" {...props}></Icon>

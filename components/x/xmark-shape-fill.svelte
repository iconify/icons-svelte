<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vck12cbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vck12cbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:xmark-shape-fill" {...props}></Icon>

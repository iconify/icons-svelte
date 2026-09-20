<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmuuir_dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dmuuir_dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:text-formatting-strikethrough" {...props}></Icon>

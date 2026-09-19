<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiftl3blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uiftl3blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:table-computed" {...props}></Icon>

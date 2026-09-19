<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/demkhgwzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="demkhgwzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stop-filled" {...props}></Icon>

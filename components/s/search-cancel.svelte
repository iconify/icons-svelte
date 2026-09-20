<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-7vjvayr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-7vjvayr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:search-cancel" {...props}></Icon>

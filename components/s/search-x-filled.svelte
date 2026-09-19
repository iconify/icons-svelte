<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx7g8xu8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx7g8xu8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-x-filled" {...props}></Icon>

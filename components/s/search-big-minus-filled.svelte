<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7ld7obdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7ld7obdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-big-minus-filled" {...props}></Icon>

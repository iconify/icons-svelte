<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r35ib4brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r35ib4brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:trending-down" {...props}></Icon>

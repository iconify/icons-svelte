<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_47-0bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_47-0bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:share-2-thin" {...props}></Icon>

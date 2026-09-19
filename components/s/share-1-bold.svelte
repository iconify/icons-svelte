<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru5b1fbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru5b1fbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:share-1-bold" {...props}></Icon>

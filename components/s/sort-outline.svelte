<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di3wnob9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di3wnob9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:sort-outline" {...props}></Icon>

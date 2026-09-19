<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhlyu95xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhlyu95xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:sort-ascending" {...props}></Icon>

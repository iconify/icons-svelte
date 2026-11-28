<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doko_h-hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doko_h-hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-list-filter-solid" {...props}></Icon>

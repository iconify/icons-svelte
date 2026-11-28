<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg1o_0azd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg1o_0azd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:search-solid" {...props}></Icon>

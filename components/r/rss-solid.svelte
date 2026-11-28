<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj07_abtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj07_abtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:rss-solid" {...props}></Icon>

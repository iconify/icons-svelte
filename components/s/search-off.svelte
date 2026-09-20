<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja_m97byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja_m97byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:search-off" {...props}></Icon>

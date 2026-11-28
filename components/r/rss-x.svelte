<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4k91_euc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4k91_euc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:rss-x" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhtlb8kso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhtlb8kso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:trending" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5-apcb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5-apcb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:search" {...props}></Icon>

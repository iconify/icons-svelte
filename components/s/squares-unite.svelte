<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xseu34bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xseu34bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:squares-unite" {...props}></Icon>

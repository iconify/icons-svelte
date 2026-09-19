<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckt3eabti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckt3eabti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:scanner-bold" {...props}></Icon>

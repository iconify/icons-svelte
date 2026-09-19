<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv-xi-bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv-xi-bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-layout" {...props}></Icon>

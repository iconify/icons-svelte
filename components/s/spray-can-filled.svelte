<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_pe8dxch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_pe8dxch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:spray-can-filled" {...props}></Icon>

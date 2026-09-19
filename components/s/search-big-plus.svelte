<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd6gj6bbb.css';
import '../../css/g/gdq0r_bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pd6gj6bbb"/><path class="gdq0r_bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-big-plus" {...props}></Icon>

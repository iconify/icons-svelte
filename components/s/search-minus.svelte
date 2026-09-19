<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uowjoqehi.css';
import '../../css/h/h2wu78b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uowjoqehi"/><path class="h2wu78b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-minus" {...props}></Icon>

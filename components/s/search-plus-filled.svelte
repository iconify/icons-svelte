<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg38nmbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg38nmbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-plus-filled" {...props}></Icon>

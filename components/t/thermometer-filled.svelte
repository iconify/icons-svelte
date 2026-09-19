<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cclx4gbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cclx4gbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:thermometer-filled" {...props}></Icon>

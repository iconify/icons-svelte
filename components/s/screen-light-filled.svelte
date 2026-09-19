<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qctaksagg.css';
import '../../css/w/wzczkxivh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="qctaksagg"/><path class="wzczkxivh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:screen-light-filled" {...props}></Icon>

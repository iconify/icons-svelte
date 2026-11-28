<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga618bbrt.css';
import '../../css/s/s1qbo6fdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ga618bbrt secondary"/><path class="primary s1qbo6fdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:star-duo" {...props}></Icon>

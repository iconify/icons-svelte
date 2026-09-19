<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwtv1pcoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":19,"height":24};
const content = `<path class="fwtv1pcoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:yahoo" {...props}></Icon>

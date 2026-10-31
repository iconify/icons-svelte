<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylmun4jqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylmun4jqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:star-half-fill-round" {...props}></Icon>

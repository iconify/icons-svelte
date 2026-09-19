<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx1a2vbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx1a2vbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:wear-hard-hat" {...props}></Icon>

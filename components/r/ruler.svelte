<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jix0ipbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jix0ipbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ruler" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjx7gcb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjx7gcb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tools-circle-filled" {...props}></Icon>

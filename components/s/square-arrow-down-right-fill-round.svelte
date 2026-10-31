<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4h-flc5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4h-flc5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-arrow-down-right-fill-round" {...props}></Icon>

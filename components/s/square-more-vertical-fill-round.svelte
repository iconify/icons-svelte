<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b15u4emsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b15u4emsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-more-vertical-fill-round" {...props}></Icon>

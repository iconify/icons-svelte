<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4se-c4fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4se-c4fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dashed-square-top-left-round" {...props}></Icon>

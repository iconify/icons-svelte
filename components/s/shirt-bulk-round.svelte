<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ija5sfmth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ija5sfmth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shirt-bulk-round" {...props}></Icon>

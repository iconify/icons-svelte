<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhe-mqb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhe-mqb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-check-corner-round" {...props}></Icon>

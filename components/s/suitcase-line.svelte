<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um07l8bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um07l8bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:suitcase-line" {...props}></Icon>

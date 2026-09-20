<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-i5xtbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-i5xtbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:solar-panel-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psjydwbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psjydwbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shopping-bag-3-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuogy9mlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuogy9mlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:square-line" {...props}></Icon>

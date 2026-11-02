<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jph56f29d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jph56f29d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:table-2-line" {...props}></Icon>

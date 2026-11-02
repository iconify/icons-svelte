<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlwseac3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlwseac3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:taj-mahal-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af-0lpb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="af-0lpb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wmo4680-90" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqun6cb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="tqun6cb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:sd" {...props}></Icon>

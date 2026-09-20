<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy7btdbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="wy7btdbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wmo4680-32" {...props}></Icon>

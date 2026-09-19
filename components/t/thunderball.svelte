<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrkgf0jsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wrkgf0jsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:thunderball" {...props}></Icon>

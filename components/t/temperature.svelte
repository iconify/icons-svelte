<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp2jyjjny.css';
import '../../css/t/t4ppgnbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jp2jyjjny"/><path class="t4ppgnbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:temperature" {...props}></Icon>

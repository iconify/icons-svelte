<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqrahty2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="jqrahty2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:school" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqd4un0bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="jqd4un0bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:travel-agency" {...props}></Icon>

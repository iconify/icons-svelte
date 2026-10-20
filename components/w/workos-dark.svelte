<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvpkry_-f.css';
import '../../css/m/m3d6pw-jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":55.4,"height":48};
const content = `<path class="kvpkry_-f"/><path class="m3d6pw-jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:workos-dark" {...props}></Icon>

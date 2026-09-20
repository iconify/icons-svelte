<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dutclc24h.css';
import '../../css/x/x5f34xbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dutclc24h"/><path class="x5f34xbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:spyder" {...props}></Icon>

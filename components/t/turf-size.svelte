<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3nbakb9b.css';
import '../../css/l/lsid_0bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="k3nbakb9b"/><path class="lsid_0bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-size" {...props}></Icon>

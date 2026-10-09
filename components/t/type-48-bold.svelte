<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kemulyb_r.css';
import '../../css/x/x-e0pwbux.css';
import '../../css/d/dnwvp9oef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kemulyb_r"/><path class="x-e0pwbux"/><path class="dnwvp9oef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:type-48-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idb1z9zzg.css';
import '../../css/k/kyzfwv8lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="idb1z9zzg"/><path class="kyzfwv8lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voilib" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umia02pax.css';
import '../../css/m/md4i0xbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="umia02pax"/><path class="md4i0xbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thumbs-up-20-bold" {...props}></Icon>

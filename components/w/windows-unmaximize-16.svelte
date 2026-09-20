<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpk85c56s.css';
import '../../css/z/zt9kpc87r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kpk85c56s"/><path clip-rule="evenodd" class="zt9kpc87r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:windows-unmaximize-16" {...props}></Icon>

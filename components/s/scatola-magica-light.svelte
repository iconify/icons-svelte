<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5py7xbsd.css';
import '../../css/w/wd2bk8qje.css';
import '../../css/e/ey4nidbgq.css';
import '../../css/x/x3sba3w-q.css';
import '../../css/p/pquylo05r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u5py7xbsd"/><path class="wd2bk8qje"/><path class="ey4nidbgq"/><path class="x3sba3w-q"/><path class="pquylo05r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scatola-magica-light" {...props}></Icon>

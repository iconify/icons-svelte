<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb44leb3z.css';
import '../../css/s/s_dxuzqlj.css';
import '../../css/l/lct3agv3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pb44leb3z"/><path class="s_dxuzqlj"/><path class="lct3agv3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visernic" {...props}></Icon>

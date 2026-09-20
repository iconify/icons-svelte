<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufwqrnbxh.css';
import '../../css/p/pgs89cb6b.css';
import '../../css/s/s_6fbubyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ufwqrnbxh"/><path class="pgs89cb6b"/><path class="s_6fbubyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:termix" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_oaq9bhw.css';
import '../../css/t/t_82l-4pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m_oaq9bhw"/><path clip-rule="evenodd" class="t_82l-4pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:safe-solid" {...props}></Icon>

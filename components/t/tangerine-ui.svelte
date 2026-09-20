<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqb812bom.css';
import '../../css/p/ph6nbhfkp.css';
import '../../css/h/hgj6s0-wz.css';
import '../../css/b/bodq3cb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tqb812bom"/><path class="ph6nbhfkp"/><path class="hgj6s0-wz"/><path class="bodq3cb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tangerine-ui" {...props}></Icon>

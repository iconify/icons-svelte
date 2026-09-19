<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzg1bwb1s.css';
import '../../css/v/vfddtzbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nzg1bwb1s"/><path class="vfddtzbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:terminal" {...props}></Icon>

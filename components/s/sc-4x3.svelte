<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp649actv.css';
import '../../css/t/twafu6bzl.css';
import '../../css/s/swd51fzfc.css';
import '../../css/j/jbrvtvlbz.css';
import '../../css/g/gb6m21box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="gp649actv"/><path class="twafu6bzl"/><path class="swd51fzfc"/><path class="jbrvtvlbz"/><path class="gb6m21box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:sc-4x3" {...props}></Icon>

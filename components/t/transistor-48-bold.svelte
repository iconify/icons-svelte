<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owfef_bia.css';
import '../../css/e/e8e1iqbrn.css';
import '../../css/m/m7c60mbxm.css';
import '../../css/b/bz-wdcbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="owfef_bia"/><path class="e8e1iqbrn"/><path class="m7c60mbxm"/><path class="bz-wdcbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:transistor-48-bold" {...props}></Icon>

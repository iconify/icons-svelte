<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/ktazicukk.css';
import '../../css/w/wrqafjrbc.css';
import '../../css/b/bmc7y_buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ktazicukk"/><path class="wrqafjrbc"/><path class="bmc7y_buz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:vacation" {...props}></Icon>

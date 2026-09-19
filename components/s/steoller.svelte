<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/j/jm4auib8w.css';
import '../../css/j/jdwxqt97w.css';
import '../../css/t/twqevhb_f.css';
import '../../css/v/vhpw_xe2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="jm4auib8w"/><circle class="jdwxqt97w"/><circle class="twqevhb_f"/><path class="vhpw_xe2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:steoller" {...props}></Icon>

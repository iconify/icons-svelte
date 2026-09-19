<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e4dtn20jx.css';
import '../../css/c/cri_ujbvz.css';
import '../../css/e/e-a_x1nrp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGC8tD5dTb"><g class="ft5dv1b6b"><path class="e4dtn20jx"/><circle class="cri_ujbvz"/><path class="e-a_x1nrp"/></g></mask></defs><path mask="url(#SVGC8tD5dTb)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:sim-card" {...props}></Icon>

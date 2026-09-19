<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lmoo01bav.css';
import '../../css/b/b2y5-tb-v.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGO2OHRbQe"><g class="ufeehvblu"><path class="lmoo01bav"/><path class="b2y5-tb-v"/></g></mask></defs><path mask="url(#SVGO2OHRbQe)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:sales-report" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti4q6eknm.css';
import '../../css/b/bkycwstta.css';
import '../../css/j/jknat6yla.css';
import '../../css/l/lba8bpl1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ti4q6eknm"><path class="bkycwstta"/><path class="jknat6yla"/><path class="lba8bpl1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:treadmill-one" {...props}></Icon>

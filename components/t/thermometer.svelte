<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/o-op5h98v.css';
import '../../css/d/d8ik5ij4p.css';
import '../../css/d/dejs93-4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="o-op5h98v"/><path class="d8ik5ij4p"/><path class="dejs93-4n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:thermometer" {...props}></Icon>

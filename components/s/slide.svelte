<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/s/su1-2fbzp.css';
import '../../css/b/b8e4web8f.css';
import '../../css/d/dvjbylbtm.css';
import '../../css/e/etssapdir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="su1-2fbzp"/><path class="b8e4web8f"/><path class="dvjbylbtm"/><path class="etssapdir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:slide" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/h/h7tcblg-d.css';
import '../../css/i/in05zubxy.css';
import '../../css/o/ovsjx9qgy.css';
import '../../css/j/j3l3upm6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="h7tcblg-d"/><circle class="in05zubxy"/><circle class="ovsjx9qgy"/><path class="j3l3upm6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:swimsuit" {...props}></Icon>

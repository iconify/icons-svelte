<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/laria4ctv.css';
import '../../css/o/ok8zy_hac.css';
import '../../css/g/goi7h-9jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="laria4ctv"/><path clip-rule="evenodd" class="ok8zy_hac"/><path class="goi7h-9jx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:test-tube" {...props}></Icon>

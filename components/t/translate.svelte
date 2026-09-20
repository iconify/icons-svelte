<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/l/lwvnupu0w.css';
import '../../css/s/sz4y6bb3f.css';
import '../../css/z/zmpl4x5yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="lwvnupu0w"/><path class="sz4y6bb3f"/><path class="zmpl4x5yw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:translate" {...props}></Icon>

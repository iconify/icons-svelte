<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/b/bo0gd_fua.css';
import '../../css/i/itwm8w2av.css';
import '../../css/z/zxmcybbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="bo0gd_fua"/><path class="itwm8w2av"/><path class="zxmcybbht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:wheelchair" {...props}></Icon>

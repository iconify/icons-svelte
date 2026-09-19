<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/p/p4anfmj7x.css';
import '../../css/b/b0bz2xbyx.css';
import '../../css/k/kr7u95b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="p4anfmj7x"/><path class="b0bz2xbyx"/><path class="kr7u95b8w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:terminal" {...props}></Icon>

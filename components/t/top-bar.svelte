<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/a/am1igebwo.css';
import '../../css/y/yeo6-kifb.css';
import '../../css/u/uhonf02fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="am1igebwo"/><path class="yeo6-kifb"/><path class="uhonf02fx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:top-bar" {...props}></Icon>

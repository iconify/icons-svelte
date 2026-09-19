<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/m/mqowuqbjp.css';
import '../../css/z/zf6nr4d2o.css';
import '../../css/g/g0v9dsb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="mqowuqbjp"/><path class="zf6nr4d2o"/><circle class="g0v9dsb-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:u-turn-left" {...props}></Icon>

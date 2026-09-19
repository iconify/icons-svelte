<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/p/prjqq_h_g.css';
import '../../css/q/quptsdbge.css';
import '../../css/l/lfsiu7tnm.css';
import '../../css/f/f0j6j6igf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><ellipse class="prjqq_h_g"/><path class="quptsdbge"/><path class="lfsiu7tnm"/><path class="f0j6j6igf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:tree-one" {...props}></Icon>

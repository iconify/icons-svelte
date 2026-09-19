<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/b/b62w8-blj.css';
import '../../css/k/kdtf-mbyl.css';
import '../../css/c/cj23v815o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><circle class="b62w8-blj"/><path class="kdtf-mbyl"/><path class="cj23v815o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:stretching-one" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/v/vkcj4bcdm.css';
import '../../css/a/ak2_4mbhu.css';
import '../../css/u/ugwidubkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="vkcj4bcdm"/><path class="ak2_4mbhu"/><path class="ugwidubkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:world" {...props}></Icon>

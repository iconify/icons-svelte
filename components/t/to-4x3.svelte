<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9qcacyl.css';
import '../../css/n/n53hu8xtg.css';
import '../../css/k/kux23acru.css';
import '../../css/i/iw2ko0b_c.css';
import '../../css/w/wtj0htkdo.css';
import '../../css/v/v34eu8bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="n53hu8xtg"/><path class="kux23acru"/><g class="iw2ko0b_c"><path class="wtj0htkdo"/><path class="v34eu8bxj"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:to-4x3" {...props}></Icon>

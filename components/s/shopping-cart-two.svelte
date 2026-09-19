<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/caaopxbqh.css';
import '../../css/t/tuqzf_bkg.css';
import '../../css/o/oth8zfbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="caaopxbqh"/><circle class="tuqzf_bkg"/><circle class="oth8zfbky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:shopping-cart-two" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxlo3ac_e.css';
import '../../css/x/xt4ay30jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="kxlo3ac_e"/><path class="xt4ay30jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:up" {...props}></Icon>

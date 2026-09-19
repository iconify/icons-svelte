<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/h/h6r38pa2g.css';
import '../../css/l/lt8k0jbcf.css';
import '../../css/z/z0p8c5bey.css';
import '../../css/q/q56tq-blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="h6r38pa2g"/><path class="lt8k0jbcf"/><path class="z0p8c5bey"/><path class="q56tq-blb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:upside-down-face" {...props}></Icon>

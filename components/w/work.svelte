<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/q/qmz_z15pg.css';
import '../../css/p/pjn3vtblj.css';
import '../../css/b/bgs7slbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="qmz_z15pg"/><path class="pjn3vtblj"/><path class="bgs7slbrn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:work" {...props}></Icon>

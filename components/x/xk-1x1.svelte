<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4-uf1bww.css';
import '../../css/v/voawabbjg.css';
import '../../css/t/tcf_pkbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r4-uf1bww"/><path class="voawabbjg"/><path class="tcf_pkbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:xk-1x1" {...props}></Icon>

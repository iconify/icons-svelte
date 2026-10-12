<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eo8wwipux.css';
import '../../css/b/bh7lyr5jh.css';
import '../../css/c/chfecmsdz.css';
import '../../css/u/ucrz1e4-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eo8wwipux"/><path class="bh7lyr5jh"/><path class="chfecmsdz"/><path class="ucrz1e4-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:snail-duotone" {...props}></Icon>

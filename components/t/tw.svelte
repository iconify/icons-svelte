<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ekamw6x8t.css';
import '../../css/p/pc_jj8btf.css';
import '../../css/v/v_2jvdpvu.css';
import '../../css/f/fac6njuzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":200};
const content = `<g class="ft5dv1b6b"><path class="ekamw6x8t"/><path class="pc_jj8btf"/><circle class="v_2jvdpvu"/><path class="fac6njuzs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:tw" {...props}></Icon>

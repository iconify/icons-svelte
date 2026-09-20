<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o__tn2b4j.css';
import '../../css/l/l_eiac87f.css';
import '../../css/e/ek4t_vbai.css';
import '../../css/b/b01e3syqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o__tn2b4j"/><path class="l_eiac87f"/><rect class="ek4t_vbai"/><rect class="b01e3syqa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:trash-duotone" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dhbt0bbiv.css';
import '../../css/v/v5ygwybkd.css';
import '../../css/r/r_iishbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dhbt0bbiv"/><path class="v5ygwybkd"/><path class="r_iishbvs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tablets-duotone" {...props}></Icon>

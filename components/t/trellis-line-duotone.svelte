<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h_393lbkl.css';
import '../../css/c/c38arbcur.css';
import '../../css/n/njxkp0atg.css';
import '../../css/k/k7pmohiui.css';
import '../../css/o/omvctkd3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h_393lbkl"/><path class="c38arbcur"/><path class="njxkp0atg"/><path class="k7pmohiui"/><path class="omvctkd3h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:trellis-line-duotone" {...props}></Icon>

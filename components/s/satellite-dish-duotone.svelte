<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/flxn7o3ta.css';
import '../../css/o/ohv1qhbhs.css';
import '../../css/l/lopzz-bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="flxn7o3ta"/><path class="ohv1qhbhs"/><path class="lopzz-bpw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:satellite-dish-duotone" {...props}></Icon>

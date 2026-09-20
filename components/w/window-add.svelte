<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w5bq_bbzq.css';
import '../../css/g/ge7v_ub0y.css';
import '../../css/h/h32jkxbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w5bq_bbzq"/><path class="ge7v_ub0y"/><path clip-rule="evenodd" class="h32jkxbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:window-add" {...props}></Icon>

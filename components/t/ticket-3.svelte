<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q1c7blwuq.css';
import '../../css/k/kw2etuk8n.css';
import '../../css/p/pvfzuob1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="q1c7blwuq"/><circle class="kw2etuk8n"/><path class="pvfzuob1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ticket-3" {...props}></Icon>

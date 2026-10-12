<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z85fdgb9r.css';
import '../../css/s/s1a2eew1e.css';
import '../../css/s/s6te4phsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z85fdgb9r"/><path class="s1a2eew1e"/><path class="s6te4phsj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-m-duotone" {...props}></Icon>

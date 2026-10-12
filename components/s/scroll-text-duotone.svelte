<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sk-2_lbxb.css';
import '../../css/c/cp13a2bsj.css';
import '../../css/f/f72ylivjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sk-2_lbxb"/><path class="cp13a2bsj"/><path class="f72ylivjo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:scroll-text-duotone" {...props}></Icon>

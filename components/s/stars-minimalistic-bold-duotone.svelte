<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nsf4icv8b.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/j/jqsfrz9lo.css';
import '../../css/h/hd4nyobgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nsf4icv8b"/><g class="mc2zb0bvp"><path class="jqsfrz9lo"/><path class="hd4nyobgw"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stars-minimalistic-bold-duotone" {...props}></Icon>

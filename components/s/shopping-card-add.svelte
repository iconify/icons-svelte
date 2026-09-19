<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t-8oj-bac.css';
import '../../css/c/cvk2qf2tj.css';
import '../../css/r/rj20s6fub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t-8oj-bac"/><path class="cvk2qf2tj"/><path class="rj20s6fub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:shopping-card-add" {...props}></Icon>

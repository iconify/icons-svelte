<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/w42vh2b3z.css';
import '../../css/c/cgy44m6jh.css';
import '../../css/u/unr76jbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w42vh2b3z"/><path class="cgy44m6jh"/><path class="unr76jbhr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slider-vertical-minimalistic-line-duotone" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hq-5njbjh.css';
import '../../css/g/gmsfucc8d.css';
import '../../css/n/nq90nsjcw.css';
import '../../css/f/femrn7bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hq-5njbjh"/><path class="gmsfucc8d"/><path class="nq90nsjcw"/><path class="femrn7bog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suitcase-lines-broken" {...props}></Icon>

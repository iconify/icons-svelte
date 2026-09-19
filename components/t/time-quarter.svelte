<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bql_2u4-a.css';
import '../../css/u/uwprsn25p.css';
import '../../css/d/d8sy1ipse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bql_2u4-a"/><path class="uwprsn25p"/><path class="d8sy1ipse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:time-quarter" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gu943ccdr.css';
import '../../css/i/it7nrybuq.css';
import '../../css/d/dzd7g3bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gu943ccdr"/><path class="it7nrybuq"/><path class="dzd7g3bgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sushi-02" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o9z1up3bw.css';
import '../../css/m/m88ceybjj.css';
import '../../css/c/cg9kg7iup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o9z1up3bw"/><path class="m88ceybjj"/><path class="cg9kg7iup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:setting-done-02" {...props}></Icon>

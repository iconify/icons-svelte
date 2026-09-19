<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zcrig_nhd.css';
import '../../css/p/piq9lw_yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="shield-tick-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="zcrig_nhd"/><path class="piq9lw_yy"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:shield-tick-outline" {...props}></Icon>

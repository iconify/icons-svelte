<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zbehsk69m.css';
import '../../css/e/evwpmfbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sliders-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="zbehsk69m"/><path class="evwpmfbcj"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:sliders-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sss_nfbgc.css';
import '../../css/b/bztkctbob.css';
import '../../css/m/m-wjl1bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<g class="sss_nfbgc"><path class="bztkctbob"/><path class="m-wjl1bwa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:simplify" {...props}></Icon>

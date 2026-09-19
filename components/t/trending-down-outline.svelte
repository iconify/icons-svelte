<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/ru7780bjq.css';
import '../../css/z/zmoqu4uqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="trending-down-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="ru7780bjq"/><path class="zmoqu4uqb"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:trending-down-outline" {...props}></Icon>

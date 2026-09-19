<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/hjw279zux.css';
import '../../css/q/qb9lt7bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="search-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="hjw279zux"/><path class="qb9lt7bxy"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:search-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/x/xc9_4i9cf.css';
import '../../css/t/t4sptf3kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="user-add-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="xc9_4i9cf"/><path class="t4sptf3kw"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:user-add-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bieyuq2ue.css';
import '../../css/d/d9or84w3r.css';
import '../../css/f/frytnybvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="bieyuq2ue"/><path clip-rule="evenodd" class="d9or84w3r"/><path class="frytnybvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:vomitting" {...props}></Icon>

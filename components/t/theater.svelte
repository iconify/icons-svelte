<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/r/ra73nz3sb.css';
import '../../css/g/g59ctu1kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path clip-rule="evenodd" class="ra73nz3sb"/><path class="g59ctu1kl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:theater" {...props}></Icon>

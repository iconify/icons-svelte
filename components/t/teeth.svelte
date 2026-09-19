<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/c/c8p3g3byb.css';
import '../../css/a/acjzmsjdx.css';
import '../../css/p/pvmqixbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="c8p3g3byb"/><path class="acjzmsjdx"/><path class="pvmqixbkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:teeth" {...props}></Icon>

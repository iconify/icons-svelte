<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hf8y7jbvt.css';
import '../../css/f/fh-d-swvt.css';
import '../../css/r/r8sdp5bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="hf8y7jbvt"/><path clip-rule="evenodd" class="fh-d-swvt"/><path class="r8sdp5bdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:syphilis-alt" {...props}></Icon>

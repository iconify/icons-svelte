<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zafm_pb1a.css';
import '../../css/i/i0otw5b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4.5};
const content = `<g class="cuyn6tgcc"><path class="zafm_pb1a"/><path class="i0otw5b8v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:stumbleupon" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb4g91bhl.css';
import '../../css/z/z2z_iactg.css';
import '../../css/d/df5r14bpg.css';
import '../../css/y/y4mtfplia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vb4g91bhl"/><path class="z2z_iactg"/><path class="df5r14bpg"/><path class="y4mtfplia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:sausage" {...props}></Icon>

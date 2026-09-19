<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfcbzqdzf.css';
import '../../css/l/lqc9yhstq.css';
import '../../css/b/b8lwe5bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="cfcbzqdzf"/><path clip-rule="evenodd" class="lqc9yhstq"/><path class="b8lwe5bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:wifi" {...props}></Icon>

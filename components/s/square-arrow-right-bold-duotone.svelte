<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edf2mabxb.css';
import '../../css/b/bkvj9ck2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edf2mabxb"/><path class="bkvj9ck2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-right-bold-duotone" {...props}></Icon>

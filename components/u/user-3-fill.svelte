<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpwvazbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpwvazbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-3-fill" {...props}></Icon>

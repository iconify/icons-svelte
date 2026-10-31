<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf-ei04hx.css';
import '../../css/f/faw3i3g2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="lf-ei04hx"/><path class="faw3i3g2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:semaphore-signal" {...props}></Icon>

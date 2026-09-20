<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jajm5-bsz.css';
import '../../css/k/k_heijbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jajm5-bsz"/><path class="k_heijbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sticker-fill" {...props}></Icon>

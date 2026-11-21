<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tok2xfb_t.css';
import '../../css/c/cp5kib_ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tok2xfb_t"/><path class="cp5kib_ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-arrow-right-exit-filled" {...props}></Icon>

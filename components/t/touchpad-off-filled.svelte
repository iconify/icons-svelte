<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb_f6kbki.css';
import '../../css/z/zb_q1oboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb_f6kbki"/><path class="zb_q1oboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:touchpad-off-filled" {...props}></Icon>

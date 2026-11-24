<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf-j6_d6b.css';
import '../../css/t/t45b4tbro.css';
import '../../css/f/f1ziukbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yf-j6_d6b"/><path class="t45b4tbro"/><path class="f1ziukbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:wifi-lock-filled" {...props}></Icon>

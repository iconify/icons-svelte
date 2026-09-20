<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl8q1_1nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kl8q1_1nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:scanner-bar-code" {...props}></Icon>

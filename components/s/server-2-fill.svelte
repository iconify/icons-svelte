<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0a2-vbzo.css';
import '../../css/c/c9bbww2xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0a2-vbzo"/><path class="c9bbww2xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:server-2-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkr0r0bta.css';
import '../../css/q/qw6hk3bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkr0r0bta"/><path class="qw6hk3bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:train-3-line" {...props}></Icon>

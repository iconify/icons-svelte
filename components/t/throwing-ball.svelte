<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw1t09u-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qw1t09u-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:throwing-ball" {...props}></Icon>

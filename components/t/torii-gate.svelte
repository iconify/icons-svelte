<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pda79djdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pda79djdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:torii-gate" {...props}></Icon>

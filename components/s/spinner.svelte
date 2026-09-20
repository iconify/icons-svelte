<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udpzpgm1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udpzpgm1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:spinner" {...props}></Icon>

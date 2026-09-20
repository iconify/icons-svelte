<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-f93z-og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-f93z-og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:virtual-coin-crypto-ethereum-bold" {...props}></Icon>

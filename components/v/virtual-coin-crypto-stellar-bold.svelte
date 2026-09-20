<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaw89wbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aaw89wbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:virtual-coin-crypto-stellar-bold" {...props}></Icon>

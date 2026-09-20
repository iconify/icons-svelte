<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldglyfi2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldglyfi2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:watch-circle-bluetooth-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_37uldgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_37uldgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:steinberg-logo-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsa254b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsa254b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:wallet-alt-03" {...props}></Icon>

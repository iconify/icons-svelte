<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysk_kx6wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ysk_kx6wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:shield-cross-solid" {...props}></Icon>

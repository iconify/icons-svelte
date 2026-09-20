<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu-_jv4ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nu-_jv4ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:transfer-truck-time-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trm18ccjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trm18ccjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:zootool-logo-solid" {...props}></Icon>

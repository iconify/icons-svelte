<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i23t-ebno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i23t-ebno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:visa-logo-block" {...props}></Icon>

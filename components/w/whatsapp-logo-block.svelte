<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaf955bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aaf955bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:whatsapp-logo-block" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhtwmwb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xhtwmwb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:tunein-logo-block" {...props}></Icon>

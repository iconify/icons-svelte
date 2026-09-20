<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ednels0te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ednels0te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:wise-logo-solid" {...props}></Icon>

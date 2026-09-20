<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjqa4gy1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cjqa4gy1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:steinberg-logo-block" {...props}></Icon>

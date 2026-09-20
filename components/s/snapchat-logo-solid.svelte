<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-omnkb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-omnkb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:snapchat-logo-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut7h2oafm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut7h2oafm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:tumblr-logo-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/str6i-nan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="str6i-nan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:youtube-gaming-logo-3-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvx6p8-na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cvx6p8-na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:youtube-clip-logo-block" {...props}></Icon>

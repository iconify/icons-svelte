<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w36eivbky.css';
import '../../css/i/isad52bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w36eivbky"/><path class="isad52bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wallet-3" {...props}></Icon>

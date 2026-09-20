<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhrm0qbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhrm0qbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-error-1-filled" {...props}></Icon>

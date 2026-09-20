<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e88q4ab4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e88q4ab4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield-lock-filled" {...props}></Icon>

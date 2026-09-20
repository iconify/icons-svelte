<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7bn6nb8f.css';
import '../../css/i/izn9dcbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7bn6nb8f"/><path class="izn9dcbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:unmute-24" {...props}></Icon>

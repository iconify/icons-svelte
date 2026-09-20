<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8i-iccby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b8i-iccby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:video-frame-outline" {...props}></Icon>

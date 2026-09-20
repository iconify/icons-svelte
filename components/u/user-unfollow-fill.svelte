<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm4oul90u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm4oul90u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-unfollow-fill" {...props}></Icon>

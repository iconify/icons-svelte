<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdn_2bb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdn_2bb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-unfollow-line" {...props}></Icon>

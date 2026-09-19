<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvq7vy1ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvq7vy1ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-right-02" {...props}></Icon>

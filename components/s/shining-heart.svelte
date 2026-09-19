<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et392opow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="et392opow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shining-heart" {...props}></Icon>

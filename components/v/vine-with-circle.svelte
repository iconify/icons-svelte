<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9vy3s1jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v9vy3s1jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:vine-with-circle" {...props}></Icon>

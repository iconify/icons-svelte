<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fav6gibqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fav6gibqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:tag" {...props}></Icon>

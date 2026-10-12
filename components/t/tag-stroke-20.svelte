<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxyh9s5lq.css';
import '../../css/f/f5hnvrbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kxyh9s5lq"/><path class="f5hnvrbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:tag-stroke-20" {...props}></Icon>

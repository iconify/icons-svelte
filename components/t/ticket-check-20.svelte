<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl41xxbat.css';
import '../../css/j/jeuojelkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tl41xxbat"/><path class="jeuojelkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ticket-check-20" {...props}></Icon>

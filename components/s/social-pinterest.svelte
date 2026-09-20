<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj6s_8m8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":976};
const content = `<path class="hj6s_8m8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-pinterest" {...props}></Icon>

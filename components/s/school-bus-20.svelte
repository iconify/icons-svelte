<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmf-m7bxg.css';
import '../../css/b/bcx0b9bfi.css';
import '../../css/h/hnhi0q8cq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mmf-m7bxg"/><path class="bcx0b9bfi"/><path class="hnhi0q8cq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:school-bus-20" {...props}></Icon>

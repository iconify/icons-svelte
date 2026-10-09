<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq_b3258o.css';
import '../../css/h/his60jocq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aq_b3258o"/><path class="his60jocq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:unlock-20-bold" {...props}></Icon>

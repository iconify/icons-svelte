<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ammh8jlyd.css';
import '../../css/i/iux9rx_ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ammh8jlyd"/><path class="iux9rx_ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:used-cooking-oil-20-bold" {...props}></Icon>

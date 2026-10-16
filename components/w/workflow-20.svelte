<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl75yhb6l.css';
import '../../css/u/uqpad_ykf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tl75yhb6l"/><path class="uqpad_ykf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:workflow-20" {...props}></Icon>

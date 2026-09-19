<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd9w_l7jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kd9w_l7jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:splashy-stream" {...props}></Icon>

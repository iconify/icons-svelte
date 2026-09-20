<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsz5w_b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zsz5w_b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:runson-light" {...props}></Icon>

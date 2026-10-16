<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjzn3h8oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mjzn3h8oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:star-rating-48" {...props}></Icon>

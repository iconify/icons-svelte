<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqddq8bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mqddq8bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:send-right-outline" {...props}></Icon>

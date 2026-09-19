<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o755flidq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o755flidq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:sign" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey_kr2fcq.css';
import '../../css/f/f8js4o8ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ey_kr2fcq"/><path class="f8js4o8ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:train-sharp" {...props}></Icon>

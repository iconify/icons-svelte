<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7mi3lqpf.css';
import '../../css/n/n5f4dctir.css';
import '../../css/h/hwn9kbc0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<circle class="m7mi3lqpf"/><path class="n5f4dctir"/><path class="hwn9kbc0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-center" {...props}></Icon>

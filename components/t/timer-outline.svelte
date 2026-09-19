<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6yzo2b5e.css';
import '../../css/q/qzignebpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o6yzo2b5e"/><path class="qzignebpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:timer-outline" {...props}></Icon>

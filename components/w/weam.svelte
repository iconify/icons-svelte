<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bogfzjklk.css';
import '../../css/q/qgbbpoxov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bogfzjklk"/><path class="qgbbpoxov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:weam" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiv8dnhip.css';
import '../../css/v/v5b4nab0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qiv8dnhip"/><path class="v5b4nab0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tidal-stream-turbine-20" {...props}></Icon>

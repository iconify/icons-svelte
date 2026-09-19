<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4vczpcbl.css';
import '../../css/q/qy0mhroxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="d4vczpcbl"/><path class="qy0mhroxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:torsos-all-female" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5llwvbom.css';
import '../../css/m/moizz8y3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g5llwvbom"/><path class="moizz8y3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:upload-48-bold" {...props}></Icon>

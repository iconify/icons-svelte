<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nris9bbgu.css';
import '../../css/a/ak9f-hbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nris9bbgu"/><path class="ak9f-hbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:saw-48" {...props}></Icon>

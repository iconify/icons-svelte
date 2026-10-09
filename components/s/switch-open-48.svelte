<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-dmmacii.css';
import '../../css/b/bo2mh3bzn.css';
import '../../css/u/ua8x71bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j-dmmacii"/><path class="bo2mh3bzn"/><path class="ua8x71bme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:switch-open-48" {...props}></Icon>

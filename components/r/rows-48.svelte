<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si3nracbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="si3nracbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rows-48" {...props}></Icon>

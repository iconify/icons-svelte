<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf47s3b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tf47s3b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-48-bold" {...props}></Icon>

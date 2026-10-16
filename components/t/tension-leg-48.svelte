<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvx4u6ucp.css';
import '../../css/g/grugfhhze.css';
import '../../css/y/y-445ob1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uvx4u6ucp"/><path class="grugfhhze"/><path class="y-445ob1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tension-leg-48" {...props}></Icon>

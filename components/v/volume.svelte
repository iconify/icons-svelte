<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3n4852oq.css';
import '../../css/o/onfml7bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="k3n4852oq"/><path class="onfml7bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:volume" {...props}></Icon>

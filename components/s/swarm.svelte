<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltlf2ibuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ltlf2ibuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:swarm" {...props}></Icon>

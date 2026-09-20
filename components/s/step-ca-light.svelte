<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap7k5ib6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ap7k5ib6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:step-ca-light" {...props}></Icon>

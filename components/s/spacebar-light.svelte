<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns55a6b6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ns55a6b6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spacebar-light" {...props}></Icon>

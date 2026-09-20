<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km15ajb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="km15ajb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:warning-multiple" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd0mncbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kd0mncbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:ws-analytics" {...props}></Icon>

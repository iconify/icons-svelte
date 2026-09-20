<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so9gubb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="so9gubb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:virola-dark" {...props}></Icon>

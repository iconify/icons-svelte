<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opmrojb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="opmrojb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ynab-light" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouf82zblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ouf82zblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visual-db-light" {...props}></Icon>

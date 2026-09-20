<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szpeyz0sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="szpeyz0sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wells-fargo-dark" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa6r0qb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aa6r0qb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tidarr-light" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np9k7qb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="np9k7qb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:technitium-light" {...props}></Icon>

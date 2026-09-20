<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu3jh-bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gu3jh-bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vanilla-cookbook-light" {...props}></Icon>

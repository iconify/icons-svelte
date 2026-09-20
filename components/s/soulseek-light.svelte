<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya0hl4bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ya0hl4bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:soulseek-light" {...props}></Icon>

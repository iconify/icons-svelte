<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjvq-5bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bjvq-5bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ticktick-light" {...props}></Icon>

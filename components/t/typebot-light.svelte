<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbbj9dbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bbbj9dbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typebot-light" {...props}></Icon>

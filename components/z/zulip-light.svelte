<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r25y7b4nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r25y7b4nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zulip-light" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xopw7kbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xopw7kbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stash-dark" {...props}></Icon>

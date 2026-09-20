<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6usd9b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v6usd9b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:seedsync-light" {...props}></Icon>

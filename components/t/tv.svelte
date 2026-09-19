<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7unewr-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7unewr-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:tv" {...props}></Icon>

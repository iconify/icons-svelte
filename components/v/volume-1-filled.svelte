<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8qfq31zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8qfq31zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:volume-1-filled" {...props}></Icon>

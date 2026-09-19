<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfe-jnboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfe-jnboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:shield-exclamation" {...props}></Icon>

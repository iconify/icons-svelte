<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9wya7brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v9wya7brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:stroke-line-join-round-duotone" {...props}></Icon>

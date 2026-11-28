<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls8624bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls8624bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:webhook-solid" {...props}></Icon>

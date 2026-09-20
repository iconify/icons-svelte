<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vog3f1bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vog3f1bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tombstone" {...props}></Icon>

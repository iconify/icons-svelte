<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j96papb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j96papb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:teamspeak" {...props}></Icon>

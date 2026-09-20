<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li1hz3b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li1hz3b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:selection" {...props}></Icon>

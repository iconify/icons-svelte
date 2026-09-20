<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss5a9poia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss5a9poia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:store-settings" {...props}></Icon>

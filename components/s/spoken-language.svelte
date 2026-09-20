<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nksmbhboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nksmbhboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:spoken-language" {...props}></Icon>

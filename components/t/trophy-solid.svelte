<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me89-bcny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="me89-bcny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:trophy-solid" {...props}></Icon>

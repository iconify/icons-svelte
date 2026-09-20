<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_v7y6nre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_v7y6nre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:star-half-filled" {...props}></Icon>

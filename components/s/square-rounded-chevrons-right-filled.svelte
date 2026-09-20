<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smx79xg7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smx79xg7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-chevrons-right-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqtv91-ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqtv91-ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:speakerphone" {...props}></Icon>

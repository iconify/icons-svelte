<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi8c8mbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi8c8mbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-p-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnwo_2b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnwo_2b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:zoho" {...props}></Icon>

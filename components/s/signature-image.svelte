<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mga236b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mga236b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:signature-image" {...props}></Icon>

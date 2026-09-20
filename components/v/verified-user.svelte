<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aioi5mbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aioi5mbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:verified-user" {...props}></Icon>

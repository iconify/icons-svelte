<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elpxm65ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elpxm65ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:settings-filled" {...props}></Icon>

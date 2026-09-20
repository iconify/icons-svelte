<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb-a62bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb-a62bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:send-hor-duotone-line" {...props}></Icon>

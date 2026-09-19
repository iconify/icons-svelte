<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brewhf1tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="brewhf1tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:send-solid" {...props}></Icon>

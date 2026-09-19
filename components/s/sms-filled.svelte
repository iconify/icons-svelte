<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s55pzcced.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s55pzcced"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sms-filled" {...props}></Icon>

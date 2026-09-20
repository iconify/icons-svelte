<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h15weabey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h15weabey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:zwave" {...props}></Icon>

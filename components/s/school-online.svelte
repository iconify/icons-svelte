<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qofpi6brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qofpi6brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:school-online" {...props}></Icon>

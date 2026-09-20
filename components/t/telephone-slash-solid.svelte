<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6ls90bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6ls90bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:telephone-slash-solid" {...props}></Icon>

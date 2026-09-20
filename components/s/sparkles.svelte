<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hew9mwplw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hew9mwplw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:sparkles" {...props}></Icon>

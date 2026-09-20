<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4sqbf30h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4sqbf30h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:yen-circle-solid" {...props}></Icon>

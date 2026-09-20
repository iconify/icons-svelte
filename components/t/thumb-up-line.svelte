<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm935zban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm935zban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thumb-up-line" {...props}></Icon>

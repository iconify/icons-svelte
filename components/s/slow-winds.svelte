<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/har_mcb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="har_mcb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:slow-winds" {...props}></Icon>

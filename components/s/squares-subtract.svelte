<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qynpu4n-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qynpu4n-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:squares-subtract" {...props}></Icon>

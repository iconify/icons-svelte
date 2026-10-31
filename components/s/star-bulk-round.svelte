<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s06ujyb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s06ujyb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:star-bulk-round" {...props}></Icon>

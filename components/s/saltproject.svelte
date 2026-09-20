<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqriu2blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqriu2blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:saltproject" {...props}></Icon>

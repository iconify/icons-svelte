<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9hdssdgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9hdssdgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tnt" {...props}></Icon>

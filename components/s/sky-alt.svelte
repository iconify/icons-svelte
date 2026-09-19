<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ron528b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ron528b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sky-alt" {...props}></Icon>

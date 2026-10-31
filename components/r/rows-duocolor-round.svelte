<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs_vv7b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs_vv7b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:rows-duocolor-round" {...props}></Icon>

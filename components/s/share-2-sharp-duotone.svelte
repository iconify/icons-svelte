<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4p6zwb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4p6zwb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:share-2-sharp-duotone" {...props}></Icon>

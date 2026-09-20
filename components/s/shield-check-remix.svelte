<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8ul1ydbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q8ul1ydbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shield-check-remix" {...props}></Icon>

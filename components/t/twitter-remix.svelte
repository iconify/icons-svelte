<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df5re8b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="df5re8b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:twitter-remix" {...props}></Icon>

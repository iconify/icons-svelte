<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgtdl3gbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kgtdl3gbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-happy-remix" {...props}></Icon>

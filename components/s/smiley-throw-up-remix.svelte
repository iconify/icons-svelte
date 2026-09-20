<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fihtkvz7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fihtkvz7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-throw-up-remix" {...props}></Icon>

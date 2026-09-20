<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhs37gbzw.css';
import '../../css/e/ezc6ubmmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhs37gbzw"/><path class="ezc6ubmmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smiley-cheeky" {...props}></Icon>

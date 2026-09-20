<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsv0algms.css';
import '../../css/i/i3h9pj49l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hsv0algms"/><path clip-rule="evenodd" class="i3h9pj49l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:tape-16" {...props}></Icon>

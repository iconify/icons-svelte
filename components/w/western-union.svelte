<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf1nmd-il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rf1nmd-il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:western-union" {...props}></Icon>

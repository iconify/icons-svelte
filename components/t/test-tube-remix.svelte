<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdzlb1bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xdzlb1bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:test-tube-remix" {...props}></Icon>

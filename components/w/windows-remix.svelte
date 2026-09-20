<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlwb603jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qlwb603jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:windows-remix" {...props}></Icon>

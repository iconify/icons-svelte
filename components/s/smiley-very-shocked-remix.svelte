<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do2dhcc6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="do2dhcc6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-very-shocked-remix" {...props}></Icon>

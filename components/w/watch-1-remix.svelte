<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh6rurf5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oh6rurf5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:watch-1-remix" {...props}></Icon>

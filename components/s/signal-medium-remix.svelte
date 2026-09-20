<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b21_4_b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b21_4_b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signal-medium-remix" {...props}></Icon>

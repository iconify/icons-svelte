<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4y7dbcip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j4y7dbcip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:virtual-reality-remix" {...props}></Icon>

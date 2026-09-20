<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tupo72bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tupo72bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:select-circle-area-1-remix" {...props}></Icon>

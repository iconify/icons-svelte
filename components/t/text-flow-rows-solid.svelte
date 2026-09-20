<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drej47b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="drej47b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:text-flow-rows-solid" {...props}></Icon>

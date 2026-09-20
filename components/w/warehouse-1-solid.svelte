<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1pp6bkda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1pp6bkda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:warehouse-1-solid" {...props}></Icon>

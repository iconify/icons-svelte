<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufu-hccsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ufu-hccsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:screwdriver-wrench-remix" {...props}></Icon>

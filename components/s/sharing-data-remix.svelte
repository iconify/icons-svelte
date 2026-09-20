<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyxacac6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iyxacac6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sharing-data-remix" {...props}></Icon>

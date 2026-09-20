<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9msasz7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9msasz7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:star-2-remix" {...props}></Icon>

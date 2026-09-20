<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtdofk4_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gtdofk4_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:tree-3-remix" {...props}></Icon>

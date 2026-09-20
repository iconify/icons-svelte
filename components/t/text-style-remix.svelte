<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ainhmmwst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ainhmmwst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:text-style-remix" {...props}></Icon>

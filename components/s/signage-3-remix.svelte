<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uduzp3v7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uduzp3v7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:signage-3-remix" {...props}></Icon>

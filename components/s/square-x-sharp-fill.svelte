<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb03xai3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jb03xai3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-x-sharp-fill" {...props}></Icon>

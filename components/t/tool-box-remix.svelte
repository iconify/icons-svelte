<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0l-glbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f0l-glbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:tool-box-remix" {...props}></Icon>

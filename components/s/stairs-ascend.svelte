<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7jml-bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f7jml-bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:stairs-ascend" {...props}></Icon>

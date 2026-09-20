<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqb70dbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vqb70dbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:waving-hand-remix" {...props}></Icon>

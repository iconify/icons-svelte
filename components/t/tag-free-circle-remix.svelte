<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmps88u4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mmps88u4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:tag-free-circle-remix" {...props}></Icon>

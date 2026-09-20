<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn6c7gbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zn6c7gbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:undo-filled" {...props}></Icon>

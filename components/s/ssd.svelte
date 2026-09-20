<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcmy27vvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rcmy27vvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ssd" {...props}></Icon>

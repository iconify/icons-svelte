<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_op9ivop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h_op9ivop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:watch-charge" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozvdwcc6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ozvdwcc6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:send-square-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5ejnm66l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x5ejnm66l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-circle-filled" {...props}></Icon>

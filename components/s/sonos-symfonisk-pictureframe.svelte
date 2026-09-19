<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a60w55xio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a60w55xio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-symfonisk-pictureframe" {...props}></Icon>

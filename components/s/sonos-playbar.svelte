<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv42co59p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv42co59p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-playbar" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n32ndfh3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n32ndfh3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-move" {...props}></Icon>

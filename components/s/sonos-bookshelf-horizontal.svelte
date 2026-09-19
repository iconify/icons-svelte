<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iifssrben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iifssrben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-bookshelf-horizontal" {...props}></Icon>

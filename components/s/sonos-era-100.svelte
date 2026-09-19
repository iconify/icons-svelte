<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbdhombsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbdhombsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-era-100" {...props}></Icon>

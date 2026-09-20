<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irbpn6bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irbpn6bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:yabai" {...props}></Icon>

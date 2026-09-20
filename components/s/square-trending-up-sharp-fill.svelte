<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woe3q0b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woe3q0b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-trending-up-sharp-fill" {...props}></Icon>

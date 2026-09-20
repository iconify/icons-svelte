<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psv555bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="psv555bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:router-wifi-network-remix" {...props}></Icon>

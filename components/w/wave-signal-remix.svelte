<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp6na81yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vp6na81yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:wave-signal-remix" {...props}></Icon>

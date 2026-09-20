<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw0hygbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw0hygbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:streamlake" {...props}></Icon>

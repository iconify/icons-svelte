<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf282rbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jf282rbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:vertical-slider-2-remix" {...props}></Icon>

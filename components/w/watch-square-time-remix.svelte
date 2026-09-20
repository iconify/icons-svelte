<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um5mxq8ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="um5mxq8ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:watch-square-time-remix" {...props}></Icon>

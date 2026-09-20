<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1y_909lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y1y_909lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-multiple-circle-remix" {...props}></Icon>

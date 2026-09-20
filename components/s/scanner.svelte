<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr0eb-jog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr0eb-jog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:scanner" {...props}></Icon>

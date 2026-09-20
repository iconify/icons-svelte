<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mguys6byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mguys6byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-arrow-left2" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygozzlopj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ygozzlopj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:satellite-dish-solid" {...props}></Icon>

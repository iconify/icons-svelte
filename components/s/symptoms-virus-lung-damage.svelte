<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhtifodgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhtifodgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:symptoms-virus-lung-damage" {...props}></Icon>

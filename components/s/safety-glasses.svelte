<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlrmkhjmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlrmkhjmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:safety-glasses" {...props}></Icon>

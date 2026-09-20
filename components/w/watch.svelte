<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_evcpt4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_evcpt4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:watch" {...props}></Icon>

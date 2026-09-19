<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjkl8cb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hjkl8cb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:wind-energy-filled" {...props}></Icon>

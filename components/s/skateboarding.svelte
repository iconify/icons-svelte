<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmzjqjb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmzjqjb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:skateboarding" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmk0qacjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmk0qacjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:tab" {...props}></Icon>

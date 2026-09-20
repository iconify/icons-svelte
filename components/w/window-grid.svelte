<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-5d3-a9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-5d3-a9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:window-grid" {...props}></Icon>

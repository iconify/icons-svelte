<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if-t8gblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if-t8gblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:umbrella-solid" {...props}></Icon>

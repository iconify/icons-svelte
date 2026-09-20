<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0ak4m-da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0ak4m-da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wheelchair-accessibility" {...props}></Icon>

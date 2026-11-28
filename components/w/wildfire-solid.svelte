<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkgykkh-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkgykkh-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wildfire-solid" {...props}></Icon>

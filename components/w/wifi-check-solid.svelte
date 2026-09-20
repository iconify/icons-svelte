<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcqkfzbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcqkfzbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wifi-check-solid" {...props}></Icon>

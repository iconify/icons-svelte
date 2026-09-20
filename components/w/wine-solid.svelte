<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0y_56bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0y_56bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wine-solid" {...props}></Icon>

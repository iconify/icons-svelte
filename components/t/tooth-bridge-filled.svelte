<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjcs95bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjcs95bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-bridge-filled" {...props}></Icon>

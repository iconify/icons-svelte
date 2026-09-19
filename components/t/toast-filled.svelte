<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_28j75nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_28j75nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:toast-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf9hsacdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vf9hsacdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:trash-filled" {...props}></Icon>

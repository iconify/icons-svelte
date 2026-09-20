<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iko815bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iko815bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:thumbs-down" {...props}></Icon>

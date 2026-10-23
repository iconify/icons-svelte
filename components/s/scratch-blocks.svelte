<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl87dzblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl87dzblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:scratch-blocks" {...props}></Icon>

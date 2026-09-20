<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvwb37b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvwb37b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:store-slash" {...props}></Icon>

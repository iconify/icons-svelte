<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoz23tbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoz23tbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smile-heart" {...props}></Icon>

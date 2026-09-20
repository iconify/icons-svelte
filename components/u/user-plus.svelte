<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-7qc0-gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="f-7qc0-gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:user-plus" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t90x8mbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t90x8mbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:stop" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sllz7qtzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sllz7qtzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:volume-x-sharp" {...props}></Icon>

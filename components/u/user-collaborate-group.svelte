<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poifqk86i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poifqk86i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-collaborate-group" {...props}></Icon>

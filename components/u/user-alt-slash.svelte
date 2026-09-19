<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmc71fzqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="bmc71fzqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:user-alt-slash" {...props}></Icon>

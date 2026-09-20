<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7l-3ibnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y7l-3ibnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-sync-online-in-person-solid" {...props}></Icon>

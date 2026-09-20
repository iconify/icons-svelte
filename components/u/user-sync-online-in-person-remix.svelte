<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_y39n49f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h_y39n49f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-sync-online-in-person-remix" {...props}></Icon>

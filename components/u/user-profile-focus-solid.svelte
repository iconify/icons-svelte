<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3ey7ab7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q3ey7ab7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-profile-focus-solid" {...props}></Icon>

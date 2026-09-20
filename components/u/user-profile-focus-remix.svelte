<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z45lxu-fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z45lxu-fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-profile-focus-remix" {...props}></Icon>

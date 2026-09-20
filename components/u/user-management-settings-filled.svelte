<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5tbwdb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u5tbwdb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-management-settings-filled" {...props}></Icon>

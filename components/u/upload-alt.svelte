<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgwrju04h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgwrju04h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:upload-alt" {...props}></Icon>

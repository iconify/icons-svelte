<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azq7smbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azq7smbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:scale-filled" {...props}></Icon>

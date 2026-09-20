<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi-ddebor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi-ddebor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:smbr" {...props}></Icon>

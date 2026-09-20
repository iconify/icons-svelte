<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrr7lsb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hrr7lsb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:temperature-filled" {...props}></Icon>

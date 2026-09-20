<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr3af1bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hr3af1bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:torn" {...props}></Icon>

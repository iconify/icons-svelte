<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su9e4nbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="su9e4nbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:routing-2-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo-y55b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bo-y55b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:upload-brackets" {...props}></Icon>

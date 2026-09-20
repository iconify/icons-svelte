<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnc0f53hn.css';
import '../../css/f/frfm2sm4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rnc0f53hn"/><path class="frfm2sm4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:upload-fill" {...props}></Icon>

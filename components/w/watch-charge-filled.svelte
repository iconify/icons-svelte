<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb2qxybku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pb2qxybku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:watch-charge-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw3tvhq7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sw3tvhq7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sfi" {...props}></Icon>

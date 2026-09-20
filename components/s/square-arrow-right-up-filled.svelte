<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw77ssi0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uw77ssi0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-arrow-right-up-filled" {...props}></Icon>

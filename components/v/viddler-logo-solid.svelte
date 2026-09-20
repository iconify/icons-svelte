<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvtivvbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mvtivvbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:viddler-logo-solid" {...props}></Icon>

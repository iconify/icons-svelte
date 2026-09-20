<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5zt5obnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g5zt5obnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:xbox-live-logo-block" {...props}></Icon>

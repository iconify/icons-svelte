<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxs0vnbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hxs0vnbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:telos" {...props}></Icon>

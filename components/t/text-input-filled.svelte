<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd-3o55-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sd-3o55-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:text-input-filled" {...props}></Icon>

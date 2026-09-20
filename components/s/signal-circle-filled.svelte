<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er2h4db9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="er2h4db9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:signal-circle-filled" {...props}></Icon>

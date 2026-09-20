<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz4dxrb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mz4dxrb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:x" {...props}></Icon>

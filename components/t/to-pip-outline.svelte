<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsyqafb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsyqafb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:to-pip-outline" {...props}></Icon>

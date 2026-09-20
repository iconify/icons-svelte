<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlx_-9b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zlx_-9b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:server-square-cloud-outline" {...props}></Icon>

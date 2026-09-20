<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux428-b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ux428-b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:temperature-outline" {...props}></Icon>

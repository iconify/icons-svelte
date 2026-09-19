<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0dl3tbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0dl3tbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:user-add" {...props}></Icon>

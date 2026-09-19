<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o38hhdt2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o38hhdt2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:server-stack" {...props}></Icon>

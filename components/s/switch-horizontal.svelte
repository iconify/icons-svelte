<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w22h_obxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w22h_obxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:switch-horizontal" {...props}></Icon>

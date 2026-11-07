<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojtd7k2go.css';
import '../../css/d/dkbffkbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ojtd7k2go"/><path class="dkbffkbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sidebar-close-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0u_x4b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o0u_x4b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:security-camera" {...props}></Icon>

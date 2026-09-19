<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3m2r0nxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3m2r0nxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sidebar-filled" {...props}></Icon>

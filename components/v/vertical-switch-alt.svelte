<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zucdqebvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zucdqebvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:vertical-switch-alt" {...props}></Icon>

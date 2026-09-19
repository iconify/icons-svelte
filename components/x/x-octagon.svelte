<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdq6q2bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdq6q2bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:x-octagon" {...props}></Icon>

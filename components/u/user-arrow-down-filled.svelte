<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsu46ub4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsu46ub4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-arrow-down-filled" {...props}></Icon>

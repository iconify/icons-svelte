<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgm1vac6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgm1vac6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:signout" {...props}></Icon>

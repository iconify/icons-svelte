<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf6ew-d1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf6ew-d1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tado" {...props}></Icon>

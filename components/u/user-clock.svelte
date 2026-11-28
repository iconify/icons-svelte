<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3p4ubeee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3p4ubeee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:user-clock" {...props}></Icon>

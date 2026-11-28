<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z93r8zwso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z93r8zwso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:wifi-lock" {...props}></Icon>

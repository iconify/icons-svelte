<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob-lpacex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob-lpacex primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:signal-medium-duotone" {...props}></Icon>

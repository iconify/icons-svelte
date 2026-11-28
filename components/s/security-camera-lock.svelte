<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skdqmvxap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skdqmvxap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:security-camera-lock" {...props}></Icon>

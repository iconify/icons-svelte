<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm6nef19u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jm6nef19u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:smartphone-info" {...props}></Icon>

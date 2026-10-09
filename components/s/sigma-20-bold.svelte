<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y41whmtqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y41whmtqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sigma-20-bold" {...props}></Icon>

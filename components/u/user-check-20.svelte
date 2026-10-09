<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh3h573jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kh3h573jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-check-20" {...props}></Icon>

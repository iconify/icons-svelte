<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khg1ijbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khg1ijbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:stackpath" {...props}></Icon>

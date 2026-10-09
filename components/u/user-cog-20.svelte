<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufsgr437u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ufsgr437u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-cog-20" {...props}></Icon>

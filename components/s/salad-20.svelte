<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5i2jdjzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y5i2jdjzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:salad-20" {...props}></Icon>

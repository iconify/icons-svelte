<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poz0mu_8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="poz0mu_8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-20" {...props}></Icon>

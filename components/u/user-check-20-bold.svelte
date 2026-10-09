<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw2e5gb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pw2e5gb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-check-20-bold" {...props}></Icon>

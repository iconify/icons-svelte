<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru-jr9b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ru-jr9b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sync-alt" {...props}></Icon>

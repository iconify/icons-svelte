<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb9i7xbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fb9i7xbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sunny-intervals-48" {...props}></Icon>

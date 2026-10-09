<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn9n7-baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fn9n7-baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tornado-48-bold" {...props}></Icon>

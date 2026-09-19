<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bapu0m6tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bapu0m6tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:thermometer-quarter" {...props}></Icon>

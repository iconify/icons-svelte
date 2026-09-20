<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qws1l074c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qws1l074c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tube-light-left-light-right" {...props}></Icon>

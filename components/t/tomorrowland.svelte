<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekvjsvb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekvjsvb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tomorrowland" {...props}></Icon>

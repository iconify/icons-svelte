<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwtppab6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwtppab6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:time-progress-light" {...props}></Icon>

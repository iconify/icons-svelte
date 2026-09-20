<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihca-gn3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihca-gn3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tag5-filled" {...props}></Icon>

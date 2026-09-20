<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqk0ldt8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqk0ldt8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tram" {...props}></Icon>

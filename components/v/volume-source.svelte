<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb86f38iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb86f38iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:volume-source" {...props}></Icon>

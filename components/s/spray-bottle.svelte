<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsaq0vbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsaq0vbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:spray-bottle" {...props}></Icon>

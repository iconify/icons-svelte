<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o21t71b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o21t71b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seat-flat-angled" {...props}></Icon>

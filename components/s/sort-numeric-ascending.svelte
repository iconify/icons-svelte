<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9qm59dbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9qm59dbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-numeric-ascending" {...props}></Icon>

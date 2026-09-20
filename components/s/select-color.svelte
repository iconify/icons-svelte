<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bibyrib3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bibyrib3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:select-color" {...props}></Icon>

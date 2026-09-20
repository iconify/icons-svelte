<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi60kxhue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi60kxhue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:size-xxxl" {...props}></Icon>

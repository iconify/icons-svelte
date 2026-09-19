<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs5wzbb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs5wzbb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:xls-01" {...props}></Icon>

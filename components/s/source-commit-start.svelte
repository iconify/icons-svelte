<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzh07nbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzh07nbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:source-commit-start" {...props}></Icon>

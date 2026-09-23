<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epqtf34dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epqtf34dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:shrimp" {...props}></Icon>

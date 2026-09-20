<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d670ywb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d670ywb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:telephone-in-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar8l_7htl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar8l_7htl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:triangle-right" {...props}></Icon>

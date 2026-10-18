<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb5q3pedd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb5q3pedd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:utensils" {...props}></Icon>

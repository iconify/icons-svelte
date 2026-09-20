<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbb__8bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbb__8bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:store-fill" {...props}></Icon>

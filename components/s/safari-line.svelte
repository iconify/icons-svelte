<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy9whxbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy9whxbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:safari-line" {...props}></Icon>

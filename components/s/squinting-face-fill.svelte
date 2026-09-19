<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz7mqwbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gz7mqwbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:squinting-face-fill" {...props}></Icon>

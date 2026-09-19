<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_33i9b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_33i9b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-exclude-alt-filled" {...props}></Icon>

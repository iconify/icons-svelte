<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laoovebwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="laoovebwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tarteaucitron" {...props}></Icon>

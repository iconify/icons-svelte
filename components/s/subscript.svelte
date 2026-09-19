<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3b13z1gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3b13z1gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:subscript" {...props}></Icon>

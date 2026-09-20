<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_l-jwbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_l-jwbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sellfy" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoyc0yn7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoyc0yn7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:table-plus" {...props}></Icon>

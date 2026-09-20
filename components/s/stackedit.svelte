<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oth5bdc8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oth5bdc8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:stackedit" {...props}></Icon>

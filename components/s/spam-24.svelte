<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5q3lq8lz.css';
import '../../css/o/or-r2ccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5q3lq8lz"/><path clip-rule="evenodd" class="or-r2ccaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:spam-24" {...props}></Icon>

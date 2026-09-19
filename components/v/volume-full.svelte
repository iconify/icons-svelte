<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/himehxbog.css';
import '../../css/p/prj3bzzpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="himehxbog"/><path class="prj3bzzpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:volume-full" {...props}></Icon>

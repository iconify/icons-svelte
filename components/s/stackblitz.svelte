<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_1jr3k2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_1jr3k2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:stackblitz" {...props}></Icon>

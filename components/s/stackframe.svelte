<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8v-2u13w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8v-2u13w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:stackframe" {...props}></Icon>

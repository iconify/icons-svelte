<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdrf14ebl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdrf14ebl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:skip-next" {...props}></Icon>

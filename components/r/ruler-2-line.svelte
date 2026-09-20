<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxsky7rac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxsky7rac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ruler-2-line" {...props}></Icon>

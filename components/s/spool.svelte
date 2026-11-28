<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1hby5b5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1hby5b5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:spool" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv8pwk9eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv8pwk9eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:unlink" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9n0wgwyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9n0wgwyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sport-shoe" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj-8rmfov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bj-8rmfov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:taxi" {...props}></Icon>

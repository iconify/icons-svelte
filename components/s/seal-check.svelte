<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6-_lmbbc.css';
import '../../css/x/xvqdfg4fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6-_lmbbc"/><path class="xvqdfg4fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:seal-check" {...props}></Icon>

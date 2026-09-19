<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caq0d6f2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caq0d6f2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:square-small" {...props}></Icon>

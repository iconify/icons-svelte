<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpqcr1ehv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpqcr1ehv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shower-fill" {...props}></Icon>

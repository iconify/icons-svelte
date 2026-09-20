<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvnic1bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvnic1bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-italic" {...props}></Icon>

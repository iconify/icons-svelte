<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpqm3jbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpqm3jbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:upload" {...props}></Icon>

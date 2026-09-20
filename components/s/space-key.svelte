<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jclx62bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jclx62bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:space-key" {...props}></Icon>

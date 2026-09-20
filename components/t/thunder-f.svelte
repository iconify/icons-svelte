<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lps5dbbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7.5,"top":-3.5};
const content = `<path class="lps5dbbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:thunder-f" {...props}></Icon>

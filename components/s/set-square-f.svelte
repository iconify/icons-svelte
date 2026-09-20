<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhdb-kbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="lhdb-kbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:set-square-f" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb3udfb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb3udfb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-baseline" {...props}></Icon>

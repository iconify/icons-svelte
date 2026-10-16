<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b95cdmw4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b95cdmw4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:terminal" {...props}></Icon>

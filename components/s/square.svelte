<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3bxbjhsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3bxbjhsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:square" {...props}></Icon>

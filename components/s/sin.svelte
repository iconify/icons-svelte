<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pba35zbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pba35zbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:sin" {...props}></Icon>

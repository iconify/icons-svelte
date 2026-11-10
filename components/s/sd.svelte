<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jycn4ccgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jycn4ccgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:sd" {...props}></Icon>

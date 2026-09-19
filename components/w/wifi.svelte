<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrsk8i_6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrsk8i_6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:wifi" {...props}></Icon>

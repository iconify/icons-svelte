<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o14l0bcfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="o14l0bcfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:shopping-bag" {...props}></Icon>

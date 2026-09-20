<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn05zjzoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn05zjzoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shopping-bag" {...props}></Icon>

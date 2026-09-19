<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnrhh6btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnrhh6btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:shopping-bag-alt" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_86rhx9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_86rhx9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-menu-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fccxzfjcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fccxzfjcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:scissors-square-bold" {...props}></Icon>

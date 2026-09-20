<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzm2_nzau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pzm2_nzau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:text-align-right" {...props}></Icon>

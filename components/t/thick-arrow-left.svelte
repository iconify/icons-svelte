<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhamwsbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mhamwsbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:thick-arrow-left" {...props}></Icon>

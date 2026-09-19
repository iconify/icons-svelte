<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci9s1vbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ci9s1vbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tea" {...props}></Icon>

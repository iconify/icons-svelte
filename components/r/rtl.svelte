<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6hkx8byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":12};
const content = `<path class="b6hkx8byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:rtl" {...props}></Icon>

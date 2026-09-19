<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyt06xb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vyt06xb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:user-alt-slash" {...props}></Icon>

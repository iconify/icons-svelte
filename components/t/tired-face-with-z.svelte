<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-v_u_7lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t-v_u_7lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tired-face-with-z" {...props}></Icon>

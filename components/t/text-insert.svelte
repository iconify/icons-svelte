<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqxpd_v_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jqxpd_v_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:text-insert" {...props}></Icon>

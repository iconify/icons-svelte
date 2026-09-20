<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl3uoubvp.css';
import '../../css/b/b6eiwkb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vl3uoubvp"/><circle class="b6eiwkb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-add-rtl" {...props}></Icon>

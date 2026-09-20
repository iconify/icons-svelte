<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqx-vr3bx.css';
import '../../css/m/mj3ha3b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kqx-vr3bx"/><path class="mj3ha3b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:twin-col-select" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/wheiic_ie.css';
import '../../css/t/t_a38r7nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><rect class="wheiic_ie"/><line x1="2.25" x2="13.75" y1="8.25" y2="8.25"/><path class="t_a38r7nw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:server" {...props}></Icon>

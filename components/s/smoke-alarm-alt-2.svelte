<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au88_79si.css';
import '../../css/x/x76_u45ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au88_79si"/><path class="x76_u45ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:smoke-alarm-alt-2" {...props}></Icon>

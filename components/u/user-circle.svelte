<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_s7g_bel.css';
import '../../css/r/rz282cqep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_s7g_bel"/><path class="rz282cqep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-circle" {...props}></Icon>

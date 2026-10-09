<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm_t_jblc.css';
import '../../css/j/jztm0fbrx.css';
import '../../css/t/tbrtq8bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lm_t_jblc"/><path class="jztm0fbrx"/><path class="tbrtq8bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wood-stove-48" {...props}></Icon>

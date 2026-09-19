<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_a_rrb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m_a_rrb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:run-all" {...props}></Icon>

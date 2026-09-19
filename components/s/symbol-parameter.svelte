<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onx-m_b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="onx-m_b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-parameter" {...props}></Icon>

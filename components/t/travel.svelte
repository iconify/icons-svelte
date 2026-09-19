<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea-m_ab_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ea-m_ab_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:travel" {...props}></Icon>

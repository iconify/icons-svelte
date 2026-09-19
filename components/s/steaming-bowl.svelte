<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_rckxbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m_rckxbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:steaming-bowl" {...props}></Icon>

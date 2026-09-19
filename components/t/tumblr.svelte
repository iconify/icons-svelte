<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_588wn1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m_588wn1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:tumblr" {...props}></Icon>

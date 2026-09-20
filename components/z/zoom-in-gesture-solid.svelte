<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7m_yyd2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p7m_yyd2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:zoom-in-gesture-solid" {...props}></Icon>
